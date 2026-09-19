<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf9136b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zf9136b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:expand" {...props}></Icon>
