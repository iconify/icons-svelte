<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaur_9bvy.css';
import '../../css/f/f46yzabqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aaur_9bvy"/><path class="f46yzabqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-person-add" {...props}></Icon>
