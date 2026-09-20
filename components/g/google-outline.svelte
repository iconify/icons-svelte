<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2555zbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l2555zbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:google-outline" {...props}></Icon>
