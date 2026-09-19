<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5uh4p05j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c5uh4p05j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:equalizerthree" {...props}></Icon>
