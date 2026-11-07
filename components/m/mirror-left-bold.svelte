<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi_jt4bbp.css';
import '../../css/y/ykelgknbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi_jt4bbp"/><path class="ykelgknbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-left-bold" {...props}></Icon>
