<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adlce5bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adlce5bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lungs" {...props}></Icon>
