<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kopjo4b-r.css';
import '../../css/h/hp5x7vfmy.css';
import '../../css/x/xbsqhfb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kopjo4b-r"/><path class="hp5x7vfmy"/><path class="xbsqhfb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:book-twotone" {...props}></Icon>
