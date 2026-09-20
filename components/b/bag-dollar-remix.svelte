<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0st4ubeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0st4ubeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bag-dollar-remix" {...props}></Icon>
