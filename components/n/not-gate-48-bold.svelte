<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i04mbuhvn.css';
import '../../css/h/hf4ii3vwy.css';
import '../../css/j/j00bos-ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i04mbuhvn"/><path class="hf4ii3vwy"/><path class="j00bos-ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:not-gate-48-bold" {...props}></Icon>
