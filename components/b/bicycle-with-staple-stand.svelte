<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyoxkrbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tyoxkrbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-with-staple-stand" {...props}></Icon>
