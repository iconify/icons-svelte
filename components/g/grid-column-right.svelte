<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x384x5lmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x384x5lmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-column-right" {...props}></Icon>
