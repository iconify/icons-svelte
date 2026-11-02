<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruaav7bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruaav7bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-plug-fill" {...props}></Icon>
