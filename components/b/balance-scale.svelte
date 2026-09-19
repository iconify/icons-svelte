<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0qt-cc0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2176,"height":1792};
const content = `<path class="d0qt-cc0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:balance-scale" {...props}></Icon>
