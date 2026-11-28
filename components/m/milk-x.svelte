<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2gdnob3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2gdnob3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:milk-x" {...props}></Icon>
