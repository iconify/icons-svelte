<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv0i1zb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rv0i1zb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bookmark-line" {...props}></Icon>
