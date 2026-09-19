<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2l-sc8wc.css';
import '../../css/h/hrlvobb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i2l-sc8wc"/><path class="hrlvobb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:box-plot-twotone" {...props}></Icon>
