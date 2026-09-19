<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr60cyr2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tr60cyr2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:appstore-add-outlined" {...props}></Icon>
