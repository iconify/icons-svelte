<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh9u8-bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vh9u8-bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:qrcode-outlined" {...props}></Icon>
