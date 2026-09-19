<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-z45ybdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-z45ybdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-team" {...props}></Icon>
