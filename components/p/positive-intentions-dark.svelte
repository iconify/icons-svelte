<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyd79ccra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oyd79ccra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:positive-intentions-dark" {...props}></Icon>
