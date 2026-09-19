<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3c-h0b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="s3c-h0b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pigpeni" {...props}></Icon>
