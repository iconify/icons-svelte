<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrk88uxja.css';
import '../../css/k/kn5yufbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="kn5yufbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-bottom-48-bold" {...props}></Icon>
