<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlhs9-shh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlhs9-shh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dribdat-light" {...props}></Icon>
