<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7fxjjbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7fxjjbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:key-round-check" {...props}></Icon>
