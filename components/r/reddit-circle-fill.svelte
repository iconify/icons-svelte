<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-2gk41ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s-2gk41ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:reddit-circle-fill" {...props}></Icon>
