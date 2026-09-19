<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoc66lyzr.css';
import '../../css/p/p4gdroa5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoc66lyzr"/><path class="p4gdroa5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bus" {...props}></Icon>
