<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u441x0bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u441x0bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-x-line" {...props}></Icon>
