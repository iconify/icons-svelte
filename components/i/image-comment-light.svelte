<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ft-0tpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4ft-0tpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:image-comment-light" {...props}></Icon>
