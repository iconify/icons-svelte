<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oedqgxdbn.css';
import '../../css/u/uckwd9b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oedqgxdbn"/><path class="uckwd9b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:red-hat-dark" {...props}></Icon>
