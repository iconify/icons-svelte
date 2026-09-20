<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud97l4bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ud97l4bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:artist-song" {...props}></Icon>
