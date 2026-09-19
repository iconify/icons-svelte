<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o20yp87lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o20yp87lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:code-outlined" {...props}></Icon>
