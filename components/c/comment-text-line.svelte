<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du64cvbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du64cvbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comment-text-line" {...props}></Icon>
