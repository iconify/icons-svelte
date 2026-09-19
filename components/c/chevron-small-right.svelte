<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohawap6hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ohawap6hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-small-right" {...props}></Icon>
