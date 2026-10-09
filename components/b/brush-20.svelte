<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t22ym13gb.css';
import '../../css/q/q7uz6xnzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t22ym13gb"/><path class="q7uz6xnzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brush-20" {...props}></Icon>
