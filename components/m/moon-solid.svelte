<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tibruob8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tibruob8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:moon-solid" {...props}></Icon>
