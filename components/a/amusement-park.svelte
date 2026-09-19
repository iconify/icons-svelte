<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bno6c1bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bno6c1bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:amusement-park" {...props}></Icon>
