<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms7ncqbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms7ncqbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:line-squiggle" {...props}></Icon>
