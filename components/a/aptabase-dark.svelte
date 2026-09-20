<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amra5osci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amra5osci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aptabase-dark" {...props}></Icon>
