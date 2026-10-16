<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8s-z80le.css';
import '../../css/p/pkm70y_4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m8s-z80le"/><path class="pkm70y_4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-dots-48-bold" {...props}></Icon>
