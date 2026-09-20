<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp7k9wstt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp7k9wstt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferdium-dark" {...props}></Icon>
