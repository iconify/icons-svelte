<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kybmr1v5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kybmr1v5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-medical-x" {...props}></Icon>
