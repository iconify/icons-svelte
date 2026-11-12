<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk064txyy.css';
import '../../css/j/jz4ibqfjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="nk064txyy"/><path class="jz4ibqfjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:our-shopping-list-light" {...props}></Icon>
