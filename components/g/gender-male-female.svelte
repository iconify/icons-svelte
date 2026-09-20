<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/typ-1_bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="typ-1_bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:gender-male-female" {...props}></Icon>
