<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyu-pdxjs.css';
import '../../css/v/v-coqgbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="qyu-pdxjs"/><path class="v-coqgbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextpvr" {...props}></Icon>
