<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj_rx7aix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yj_rx7aix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:planet2-filled" {...props}></Icon>
