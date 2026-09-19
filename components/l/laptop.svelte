<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z58ye-npm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z58ye-npm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:laptop" {...props}></Icon>
