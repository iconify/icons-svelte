<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wune1aczr.css';
import '../../css/g/gwm8q7b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wune1aczr"/><path class="gwm8q7b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rolling-pin-48" {...props}></Icon>
