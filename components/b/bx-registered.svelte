<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pchomjh0v.css';
import '../../css/y/yqzwxjpgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pchomjh0v"/><path class="yqzwxjpgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-registered" {...props}></Icon>
