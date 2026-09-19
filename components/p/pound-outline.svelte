<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otckz_btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="otckz_btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pound-outline" {...props}></Icon>
