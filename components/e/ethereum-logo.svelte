<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycarj_sir.css';
import '../../css/d/d2npymh2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycarj_sir"/><path class="d2npymh2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ethereum-logo" {...props}></Icon>
