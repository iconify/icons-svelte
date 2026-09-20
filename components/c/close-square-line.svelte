<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbanj-ttg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbanj-ttg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:close-square-line" {...props}></Icon>
