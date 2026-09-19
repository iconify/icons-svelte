<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7smeqbeh.css';
import '../../css/v/va27ux4ej.css';
import '../../css/t/tsepx-fqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y7smeqbeh"/><path class="va27ux4ej"/><path class="tsepx-fqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chat-operational" {...props}></Icon>
