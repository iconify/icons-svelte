<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaugi6cfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uaugi6cfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:right-small-solid" {...props}></Icon>
