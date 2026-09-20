<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7ld7wu0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ld7wu0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-up" {...props}></Icon>
