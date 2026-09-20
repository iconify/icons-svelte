<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_9968btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_9968btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-notes" {...props}></Icon>
