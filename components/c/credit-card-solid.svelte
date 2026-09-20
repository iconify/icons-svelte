<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmhh2qtxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmhh2qtxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:credit-card-solid" {...props}></Icon>
