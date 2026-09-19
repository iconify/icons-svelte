<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cys704nul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cys704nul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:filter-solid" {...props}></Icon>
