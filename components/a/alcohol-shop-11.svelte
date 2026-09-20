<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htc46chub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="htc46chub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:alcohol-shop-11" {...props}></Icon>
