<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_6zlj1bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_6zlj1bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bookmark-minus-filled" {...props}></Icon>
