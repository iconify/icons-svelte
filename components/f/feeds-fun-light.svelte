<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkleevbel.css';
import '../../css/k/koobuxbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkleevbel"/><path class="koobuxbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feeds-fun-light" {...props}></Icon>
