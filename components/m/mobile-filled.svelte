<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss-qr7p6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ss-qr7p6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mobile-filled" {...props}></Icon>
