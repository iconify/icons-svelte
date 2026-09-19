<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbz0v2bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fbz0v2bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:qrcode" {...props}></Icon>
