<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-u9j3wiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k-u9j3wiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:gift-outlined" {...props}></Icon>
