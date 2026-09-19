<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3bu2f_4i.css';
import '../../css/k/kl4oqnb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d3bu2f_4i"/><path class="kl4oqnb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:cloud-sync" {...props}></Icon>
