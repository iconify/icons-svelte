<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7wssw66i.css';
import '../../css/t/ttkwngbky.css';
import '../../css/l/lhg-6wa8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d7wssw66i"/><circle class="ttkwngbky"/><path class="lhg-6wa8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carbon-for-mobile" {...props}></Icon>
