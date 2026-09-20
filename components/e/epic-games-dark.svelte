<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj334wbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25.548,"height":29.501,"left":3.227,"top":1.25};
const content = `<path class="oj334wbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:epic-games-dark" {...props}></Icon>
