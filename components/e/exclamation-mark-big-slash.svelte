<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyv5spbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyv5spbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:exclamation-mark-big-slash" {...props}></Icon>
