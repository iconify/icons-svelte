<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxkr6syzc.css';
import '../../css/o/o64mo7bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pxkr6syzc"/><path class="o64mo7bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-maximum" {...props}></Icon>
