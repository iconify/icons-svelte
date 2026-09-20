<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-og96_om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-og96_om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-slash" {...props}></Icon>
