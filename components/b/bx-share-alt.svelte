<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt4uo0omy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt4uo0omy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-share-alt" {...props}></Icon>
