<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tet6-1b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tet6-1b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:at-sign-solid" {...props}></Icon>
