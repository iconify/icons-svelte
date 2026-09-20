<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn66k4w8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn66k4w8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:cloud-gear" {...props}></Icon>
