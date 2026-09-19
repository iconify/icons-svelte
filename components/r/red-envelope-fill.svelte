<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc02u_bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc02u_bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:red-envelope-fill" {...props}></Icon>
