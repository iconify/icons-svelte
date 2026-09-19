<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0b2bvsvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f0b2bvsvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:asterisk" {...props}></Icon>
