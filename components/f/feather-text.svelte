<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2fhf2b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2fhf2b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:feather-text" {...props}></Icon>
