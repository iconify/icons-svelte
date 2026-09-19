<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7knn_bjg.css';
import '../../css/k/ksmczrn_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j7knn_bjg"/><path class="ksmczrn_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:button-centered" {...props}></Icon>
