<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3o9fsq7y.css';
import '../../css/j/j4njxhbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3o9fsq7y"/><path class="j4njxhbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gdms-dark" {...props}></Icon>
