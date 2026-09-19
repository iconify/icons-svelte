<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d_kn0np1m.css';
import '../../css/j/jew5n_nry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="d_kn0np1m"/><path class="jew5n_nry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:jpy" {...props}></Icon>
