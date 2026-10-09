<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il6d4vbnm.css';
import '../../css/o/o244yobqh.css';
import '../../css/d/d39zil3no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="il6d4vbnm"/><path class="o244yobqh"/><path class="d39zil3no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-van-48-bold" {...props}></Icon>
