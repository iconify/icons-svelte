<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp6i8pb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp6i8pb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:basket" {...props}></Icon>
