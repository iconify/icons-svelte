<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2aw66r3l.css';
import '../../css/w/wvsyf7maw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2aw66r3l"/><path clip-rule="evenodd" class="wvsyf7maw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:plus-circle-24" {...props}></Icon>
