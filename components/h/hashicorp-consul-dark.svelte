<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/injr7pqjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="injr7pqjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-consul-dark" {...props}></Icon>
