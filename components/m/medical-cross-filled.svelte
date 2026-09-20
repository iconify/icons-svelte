<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6-z7noub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6-z7noub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:medical-cross-filled" {...props}></Icon>
