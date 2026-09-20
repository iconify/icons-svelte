<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2voi_5he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="u2voi_5he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:brush-solid" {...props}></Icon>
