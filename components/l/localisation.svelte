<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mawmz3o9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mawmz3o9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:localisation" {...props}></Icon>
