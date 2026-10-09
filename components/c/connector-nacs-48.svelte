<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xagjmlbpr.css';
import '../../css/x/xtdm6g52u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xagjmlbpr"/><path class="xtdm6g52u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-nacs-48" {...props}></Icon>
