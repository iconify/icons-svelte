<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1770sb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1770sb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-flat-p" {...props}></Icon>
