<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh_u0hjrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_u0hjrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:combine-cells" {...props}></Icon>
