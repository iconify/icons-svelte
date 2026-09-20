<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns08hgb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns08hgb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:qq-fill" {...props}></Icon>
