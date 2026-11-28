<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugwp1vfjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ugwp1vfjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dispensing-machine-with-handled-teacup-and-saucer" {...props}></Icon>
