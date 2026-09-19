<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqys2lycf.css';
import '../../css/u/u_u3qq80h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pqys2lycf"/><path class="u_u3qq80h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:eye-invisible-filled" {...props}></Icon>
