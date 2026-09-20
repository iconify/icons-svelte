<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9z1-0b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f9z1-0b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:psp" {...props}></Icon>
