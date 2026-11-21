<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh3ngdcch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":354.674,"height":354.674,"left":180.5,"top":180.5};
const content = `<path class="oh3ngdcch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openai-light" {...props}></Icon>
