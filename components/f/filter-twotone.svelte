<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdxpj0wua.css';
import '../../css/t/tpginfnmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cdxpj0wua"/><path class="tpginfnmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:filter-twotone" {...props}></Icon>
