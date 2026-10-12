<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xccoeqbhm.css';
import '../../css/w/wqol9ac8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xccoeqbhm"/><path class="wqol9ac8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chalkboard-20" {...props}></Icon>
