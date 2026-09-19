<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhlvfjb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zhlvfjb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:comment-urgent" {...props}></Icon>
