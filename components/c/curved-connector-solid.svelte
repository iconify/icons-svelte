<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1gf99bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u1gf99bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:curved-connector-solid" {...props}></Icon>
