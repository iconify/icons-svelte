<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjpu1iqye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kjpu1iqye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:duplicate-row" {...props}></Icon>
