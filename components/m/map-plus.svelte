<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v37zb4b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v37zb4b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-plus" {...props}></Icon>
