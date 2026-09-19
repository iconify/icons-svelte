<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxp1jqbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxp1jqbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:external" {...props}></Icon>
