<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd6x0abcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd6x0abcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:cloud-disable" {...props}></Icon>
