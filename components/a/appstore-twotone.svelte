<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es1zkkb-o.css';
import '../../css/c/ca3j5lbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="es1zkkb-o"/><path class="ca3j5lbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:appstore-twotone" {...props}></Icon>
