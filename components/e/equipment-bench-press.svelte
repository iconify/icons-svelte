<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn3tp5ssv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn3tp5ssv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:equipment-bench-press" {...props}></Icon>
