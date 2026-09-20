<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkkpyin0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jkkpyin0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:location-solid" {...props}></Icon>
