<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbkbqr1mk.css';
import '../../css/h/h-szocp3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bbkbqr1mk"/><path class="h-szocp3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-switch-off" {...props}></Icon>
