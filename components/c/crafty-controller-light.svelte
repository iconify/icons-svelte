<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guz2q5bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guz2q5bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crafty-controller-light" {...props}></Icon>
