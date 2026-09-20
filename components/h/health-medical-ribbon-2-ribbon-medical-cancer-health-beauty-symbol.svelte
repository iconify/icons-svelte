<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdyaibcnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mdyaibcnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:health-medical-ribbon-2-ribbon-medical-cancer-health-beauty-symbol" {...props}></Icon>
