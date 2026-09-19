<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmh6un4qk.css';
import '../../css/i/iaergbsgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmh6un4qk"/><path class="iaergbsgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:door" {...props}></Icon>
