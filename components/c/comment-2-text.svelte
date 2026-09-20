<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg38sdwxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg38sdwxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comment-2-text" {...props}></Icon>
