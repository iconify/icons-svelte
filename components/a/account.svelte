<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmnj1mbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmnj1mbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:account" {...props}></Icon>
