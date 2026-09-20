<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se28wqbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="se28wqbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:exclamation-small-solid" {...props}></Icon>
