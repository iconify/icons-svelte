<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhmlkstlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhmlkstlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minus-cirlce" {...props}></Icon>
