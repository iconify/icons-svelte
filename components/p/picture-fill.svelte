<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y27mh5bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y27mh5bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:picture-fill" {...props}></Icon>
