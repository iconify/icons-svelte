<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrk88uxja.css';
import '../../css/h/h5cjzi0kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="h5cjzi0kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-48-bold" {...props}></Icon>
