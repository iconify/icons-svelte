<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8nmwqbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y8nmwqbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flag-alt-solid" {...props}></Icon>
