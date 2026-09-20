<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va64q7e3s.css';
import '../../css/y/ytgw6jbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="va64q7e3s"/><path class="ytgw6jbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homelable-light" {...props}></Icon>
