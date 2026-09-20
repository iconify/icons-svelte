<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg0pw-bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0pw-bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:expand-arrows" {...props}></Icon>
