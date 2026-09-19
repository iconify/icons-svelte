<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn86rrbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qn86rrbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:border-left-outlined" {...props}></Icon>
