<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6s466b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="o6s466b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:filter" {...props}></Icon>
