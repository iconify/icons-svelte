<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x93_19b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x93_19b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comment-text" {...props}></Icon>
