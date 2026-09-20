<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3qp_jb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="a3qp_jb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:moon" {...props}></Icon>
