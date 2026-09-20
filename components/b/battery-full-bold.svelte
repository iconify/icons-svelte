<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op3xropqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="op3xropqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-full-bold" {...props}></Icon>
