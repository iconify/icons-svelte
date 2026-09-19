<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxyw-hbts.css';
import '../../css/o/o0pkr5bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxyw-hbts"/><path class="o0pkr5bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-exit" {...props}></Icon>
