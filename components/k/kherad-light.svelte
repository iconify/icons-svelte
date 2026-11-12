<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_fvxx96a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_fvxx96a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kherad-light" {...props}></Icon>
