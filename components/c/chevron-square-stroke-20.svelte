<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kun0b6tvp.css';
import '../../css/f/fppjkf2zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kun0b6tvp"/><path class="fppjkf2zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-square-stroke-20" {...props}></Icon>
