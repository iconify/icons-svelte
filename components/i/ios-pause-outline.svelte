<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd01kcbfz.css';
import '../../css/n/nzce9ndyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cd01kcbfz"/><path class="nzce9ndyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pause-outline" {...props}></Icon>
