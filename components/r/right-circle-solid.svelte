<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imrmyab4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="imrmyab4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:right-circle-solid" {...props}></Icon>
