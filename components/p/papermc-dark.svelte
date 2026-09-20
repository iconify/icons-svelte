<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spvsfy5mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spvsfy5mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-dark" {...props}></Icon>
