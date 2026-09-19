<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkvbcfvyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkvbcfvyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-flat-p-alt" {...props}></Icon>
