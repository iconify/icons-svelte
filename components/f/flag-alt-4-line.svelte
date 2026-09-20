<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7w6txbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7w6txbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-alt-4-line" {...props}></Icon>
