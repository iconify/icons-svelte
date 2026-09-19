<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnrdxabwp.css';
import '../../css/v/vbp1sgblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="hnrdxabwp"/><path clip-rule="evenodd" class="vbp1sgblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nixos" {...props}></Icon>
