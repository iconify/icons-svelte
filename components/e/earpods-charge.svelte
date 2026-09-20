<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nke5fhnsv.css';
import '../../css/h/hcg_4bble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nke5fhnsv"/><path class="hcg_4bble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:earpods-charge" {...props}></Icon>
