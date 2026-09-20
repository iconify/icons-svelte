<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4a0k1k5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4a0k1k5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dunzo" {...props}></Icon>
