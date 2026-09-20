<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f11wjqhij.css';
import '../../css/o/oimetacyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f11wjqhij"/><path class="oimetacyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:discount-percent-bubble" {...props}></Icon>
