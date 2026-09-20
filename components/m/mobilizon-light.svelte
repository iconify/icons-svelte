<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kudk1ganc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kudk1ganc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mobilizon-light" {...props}></Icon>
