<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxoda9rgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kxoda9rgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:comment-draft" {...props}></Icon>
