<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2xv61bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2xv61bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-alt-circle-down-solid" {...props}></Icon>
