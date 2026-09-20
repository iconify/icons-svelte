<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7fec_l4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7fec_l4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:custom-ink" {...props}></Icon>
