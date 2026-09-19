<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh5lc4bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fh5lc4bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:instagram-fill" {...props}></Icon>
