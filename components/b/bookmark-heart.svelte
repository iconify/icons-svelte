<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfk4z3biw.css';
import '../../css/q/qi2aslb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfk4z3biw"/><path class="qi2aslb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-heart" {...props}></Icon>
