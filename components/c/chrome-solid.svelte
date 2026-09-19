<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96pf7_tx.css';
import '../../css/z/zfoilpbse.css';
import '../../css/u/uzcrctb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h96pf7_tx"/><path class="zfoilpbse"/><path class="uzcrctb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:chrome-solid" {...props}></Icon>
