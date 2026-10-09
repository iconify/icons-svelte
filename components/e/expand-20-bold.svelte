<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mli097arj.css';
import '../../css/c/c9abqnf6w.css';
import '../../css/q/qzu82cbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mli097arj"/><path class="c9abqnf6w"/><path class="qzu82cbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expand-20-bold" {...props}></Icon>
