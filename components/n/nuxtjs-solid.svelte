<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpt_g1bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rpt_g1bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nuxtjs-solid" {...props}></Icon>
