<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9q90qrgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9q90qrgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-diagonal-2" {...props}></Icon>
