<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpwqczfrc.css';
import '../../css/q/qas0_334r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpwqczfrc"/><path class="qas0_334r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:languagetool" {...props}></Icon>
