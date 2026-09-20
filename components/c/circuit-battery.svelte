<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvu_a7hvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvu_a7hvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-battery" {...props}></Icon>
