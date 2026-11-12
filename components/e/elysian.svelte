<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqk--9bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqk--9bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elysian" {...props}></Icon>
