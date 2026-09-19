<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgakgacod.css';
import '../../css/s/s0oh6wb6v.css';
import '../../css/m/mfmbc9s1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25.9,"height":16.8};
const content = `<path class="cgakgacod"/><path class="s0oh6wb6v"/><path class="mfmbc9s1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:currency" {...props}></Icon>
