<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5hztnb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w5hztnb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-pin-2-pin-push-thumbtack" {...props}></Icon>
