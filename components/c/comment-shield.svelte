<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahdm80qiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahdm80qiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-shield" {...props}></Icon>
