<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg_gupbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jg_gupbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bootstrap" {...props}></Icon>
