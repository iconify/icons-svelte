<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x64tqdbkh.css';
import '../../css/g/gr4zytbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x64tqdbkh"/><path class="gr4zytbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-molecule-20" {...props}></Icon>
