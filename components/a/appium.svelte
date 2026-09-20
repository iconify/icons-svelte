<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbm41-n1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbm41-n1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:appium" {...props}></Icon>
