<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fruxb_bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fruxb_bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:add-plus" {...props}></Icon>
