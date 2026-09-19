<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9oy42krc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o9oy42krc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:address" {...props}></Icon>
