<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbo-qbcdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbo-qbcdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-download" {...props}></Icon>
