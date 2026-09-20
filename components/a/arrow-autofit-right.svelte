<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7eff_agy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7eff_agy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-right" {...props}></Icon>
