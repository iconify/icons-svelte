<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_l2a7q7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_l2a7q7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:add-plus-circle" {...props}></Icon>
