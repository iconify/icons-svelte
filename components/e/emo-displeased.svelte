<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnudrgbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":817,"height":1000};
const content = `<path class="lnudrgbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-displeased" {...props}></Icon>
