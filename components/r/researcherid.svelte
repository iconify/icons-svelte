<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg8lg1b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="kg8lg1b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:researcherid" {...props}></Icon>
