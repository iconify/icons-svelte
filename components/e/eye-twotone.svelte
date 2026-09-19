<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwwc2ab5u.css';
import '../../css/x/xfn8r9bjr.css';
import '../../css/f/fma9jpbyl.css';
import '../../css/t/t4em2zgug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwwc2ab5u"/><path class="xfn8r9bjr"/><path class="fma9jpbyl"/><path class="t4em2zgug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:eye-twotone" {...props}></Icon>
