<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntg6q2s3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ntg6q2s3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-column-edit" {...props}></Icon>
