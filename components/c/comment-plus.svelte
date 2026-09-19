<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgqzw8ohi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zgqzw8ohi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:comment-plus" {...props}></Icon>
