<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuk6t8bzw.css';
import '../../css/n/nxma1vbuk.css';
import '../../css/x/xaosrk3sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kuk6t8bzw"/><path class="nxma1vbuk"/><path class="xaosrk3sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:carry-out-twotone" {...props}></Icon>
