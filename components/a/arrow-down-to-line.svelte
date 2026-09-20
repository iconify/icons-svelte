<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez78vac_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez78vac_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-down-to-line" {...props}></Icon>
