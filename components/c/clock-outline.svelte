<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-t9ytaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iq-t9ytaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clock-outline" {...props}></Icon>
