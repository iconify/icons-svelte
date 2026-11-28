<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl5rj6b3b.css';
import '../../css/l/las552baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xl5rj6b3b"/><path class="las552baf primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pentagon-duo" {...props}></Icon>
