<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrc4s3tzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jrc4s3tzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:remove-link-x" {...props}></Icon>
