<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx1fsfbvz.css';
import '../../css/k/kj930pbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx1fsfbvz"/><path class="kj930pbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-window-open" {...props}></Icon>
