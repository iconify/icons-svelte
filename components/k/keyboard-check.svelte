<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psp4z1bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psp4z1bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:keyboard-check" {...props}></Icon>
