<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_081rb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_081rb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:game-science" {...props}></Icon>
