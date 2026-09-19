<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbv4lnbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mbv4lnbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:layout-filled" {...props}></Icon>
