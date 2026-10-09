<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8s-z80le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m8s-z80le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-48-bold" {...props}></Icon>
