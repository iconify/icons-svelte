<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw6jrbma.css';
import '../../css/j/jg-s2j-2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw6jrbma"/><path class="jg-s2j-2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:bitcoin-logo" {...props}></Icon>
