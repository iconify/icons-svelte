<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqcdy5blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqcdy5blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:paper-plane" {...props}></Icon>
