<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_d672fqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_d672fqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flash-off" {...props}></Icon>
