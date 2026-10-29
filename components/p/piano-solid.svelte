<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzenk-b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzenk-b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:piano-solid" {...props}></Icon>
