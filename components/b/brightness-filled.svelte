<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlfn-lb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlfn-lb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:brightness-filled" {...props}></Icon>
