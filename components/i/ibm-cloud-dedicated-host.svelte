<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k43y_he5a.css';
import '../../css/q/qwvywhgtu.css';
import '../../css/v/vh1dgbcue.css';
import '../../css/y/yca0t4ank.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="k43y_he5a"/><path class="qwvywhgtu"/><circle class="vh1dgbcue"/><path class="yca0t4ank"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-dedicated-host" {...props}></Icon>
