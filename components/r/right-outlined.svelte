<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwelxlbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pwelxlbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:right-outlined" {...props}></Icon>
