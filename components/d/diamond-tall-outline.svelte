<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_mhozbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v_mhozbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:diamond-tall-outline" {...props}></Icon>
