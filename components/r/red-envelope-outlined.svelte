<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py3krehrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="py3krehrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:red-envelope-outlined" {...props}></Icon>
