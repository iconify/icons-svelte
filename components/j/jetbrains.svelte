<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmbkaq7lv.css';
import '../../css/p/pktx-jbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tmbkaq7lv"/><path class="pktx-jbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jetbrains" {...props}></Icon>
