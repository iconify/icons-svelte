<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iptfli-wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iptfli-wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-up-dashed-square-remix" {...props}></Icon>
