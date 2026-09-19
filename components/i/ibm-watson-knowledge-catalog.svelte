<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d58vsbvrf.css';
import '../../css/v/v7mge4i6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d58vsbvrf"/><path class="v7mge4i6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-knowledge-catalog" {...props}></Icon>
