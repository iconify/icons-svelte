<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz8kk_bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz8kk_bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:loop-1-remix" {...props}></Icon>
