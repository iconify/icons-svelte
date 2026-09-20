<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l12_aub-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l12_aub-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:gift-15" {...props}></Icon>
