<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clz-cx4ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clz-cx4ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-medical-check" {...props}></Icon>
