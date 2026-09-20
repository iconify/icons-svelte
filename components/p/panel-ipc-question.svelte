<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdbhn9wpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mdbhn9wpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:panel-ipc-question" {...props}></Icon>
