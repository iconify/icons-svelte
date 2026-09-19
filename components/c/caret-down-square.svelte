<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0apn84ov.css';
import '../../css/v/vku8ojb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0apn84ov"/><path class="vku8ojb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-down-square" {...props}></Icon>
