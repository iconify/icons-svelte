<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-8l8abkc.css';
import '../../css/y/yts213bsu.css';
import '../../css/m/majk71b5n.css';
import '../../css/o/ow5iplbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l-8l8abkc"/><path class="yts213bsu"/><path class="majk71b5n"/><path class="ow5iplbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dashboard-twotone" {...props}></Icon>
