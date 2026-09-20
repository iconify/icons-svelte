<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htlf_ccgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htlf_ccgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:comsol" {...props}></Icon>
