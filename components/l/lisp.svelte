<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp_2e5bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yp_2e5bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lisp" {...props}></Icon>
