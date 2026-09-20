<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpx0ywb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpx0ywb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-check" {...props}></Icon>
