<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrk88uxja.css';
import '../../css/q/qt2057bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="qt2057bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:app-window-48-bold" {...props}></Icon>
