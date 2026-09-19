<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hal55f1hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hal55f1hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fluffy-trefoil" {...props}></Icon>
