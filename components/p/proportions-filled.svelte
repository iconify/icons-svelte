<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6bd0e58x.css';
import '../../css/i/ikrljqbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6bd0e58x"/><path class="ikrljqbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:proportions-filled" {...props}></Icon>
