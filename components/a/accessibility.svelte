<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_spsnbot.css';
import '../../css/j/jgbcgmb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l_spsnbot"/><path class="jgbcgmb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:accessibility" {...props}></Icon>
