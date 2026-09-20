<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epwrcht_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epwrcht_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubernetes-dark" {...props}></Icon>
