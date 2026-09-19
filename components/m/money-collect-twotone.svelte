<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k92pv4boj.css';
import '../../css/s/s4zsohksa.css';
import '../../css/x/xc9f067ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k92pv4boj"/><path class="s4zsohksa"/><path class="xc9f067ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:money-collect-twotone" {...props}></Icon>
