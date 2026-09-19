<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkqi2gdoy.css';
import '../../css/w/waq35gbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkqi2gdoy"/><path class="waq35gbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-googleplus" {...props}></Icon>
