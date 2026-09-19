<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8v619bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="d8v619bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:aligncenter" {...props}></Icon>
