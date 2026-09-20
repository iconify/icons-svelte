<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0gkm4b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0gkm4b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:arrow-circle-right" {...props}></Icon>
