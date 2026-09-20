<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbwkt4b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gbwkt4b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-bottom-outline" {...props}></Icon>
