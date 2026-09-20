<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doooacb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":39,"height":39};
const content = `<path class="doooacb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paper" {...props}></Icon>
