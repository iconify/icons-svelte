<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an7obwbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an7obwbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:credit-card-check" {...props}></Icon>
