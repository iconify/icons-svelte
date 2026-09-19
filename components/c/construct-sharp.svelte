<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouaf7fzvu.css';
import '../../css/v/vvr-kwzju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ouaf7fzvu"/><path class="vvr-kwzju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:construct-sharp" {...props}></Icon>
