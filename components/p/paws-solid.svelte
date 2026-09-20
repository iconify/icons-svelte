<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyskdjb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zyskdjb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paws-solid" {...props}></Icon>
