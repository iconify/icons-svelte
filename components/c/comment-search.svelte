<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyvtfptam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyvtfptam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-search" {...props}></Icon>
