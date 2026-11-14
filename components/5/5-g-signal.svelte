<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvh8zkukc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvh8zkukc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:5-g-signal" {...props}></Icon>
