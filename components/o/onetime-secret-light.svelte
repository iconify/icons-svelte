<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w077uwbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w077uwbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onetime-secret-light" {...props}></Icon>
