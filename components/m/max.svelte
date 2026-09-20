<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns09k3orw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns09k3orw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:max" {...props}></Icon>
