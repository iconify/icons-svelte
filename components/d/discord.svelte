<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tym80lb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="tym80lb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:discord" {...props}></Icon>
