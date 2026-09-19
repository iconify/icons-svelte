<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbdfjabgc.css';
import '../../css/j/jzq9heogi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbdfjabgc"/><path class="jzq9heogi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-zip" {...props}></Icon>
