<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_gf1l17f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_gf1l17f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:plus-circle" {...props}></Icon>
