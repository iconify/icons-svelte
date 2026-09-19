<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udtx5jbky.css';
import '../../css/k/kggl2nbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="udtx5jbky"/><path class="kggl2nbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-incoming-filled" {...props}></Icon>
