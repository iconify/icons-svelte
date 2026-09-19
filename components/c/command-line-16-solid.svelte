<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxdpf6bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zxdpf6bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:command-line-16-solid" {...props}></Icon>
