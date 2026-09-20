<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-sbfr54f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-sbfr54f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-funnel" {...props}></Icon>
