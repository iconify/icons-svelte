<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf1_owbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf1_owbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:istio" {...props}></Icon>
