<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf0xsld2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wf0xsld2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:logout-outlined" {...props}></Icon>
