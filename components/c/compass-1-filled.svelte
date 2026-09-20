<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgcif9d1i.css';
import '../../css/j/jpcgvbsnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgcif9d1i"/><path class="jpcgvbsnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:compass-1-filled" {...props}></Icon>
