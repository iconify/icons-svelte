<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdrpvbclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kdrpvbclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:css3-outline" {...props}></Icon>
