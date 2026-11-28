<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvqcnxhdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvqcnxhdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:keyboard-off" {...props}></Icon>
