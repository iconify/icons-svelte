<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul_akom3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ul_akom3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:code" {...props}></Icon>
