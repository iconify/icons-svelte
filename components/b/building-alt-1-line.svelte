<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5rnl5bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5rnl5bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-alt-1-line" {...props}></Icon>
