<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzh98vb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh98vb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rain-medium" {...props}></Icon>
