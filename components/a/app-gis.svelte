<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkt5ohbxh.css';
import '../../css/u/ukfpmsbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary xkt5ohbxh"/><path class="ukfpmsbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-gis" {...props}></Icon>
