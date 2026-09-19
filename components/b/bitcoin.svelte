<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdn_hb7jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1024};
const content = `<path class="pdn_hb7jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bitcoin" {...props}></Icon>
