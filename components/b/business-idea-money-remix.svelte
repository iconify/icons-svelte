<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfl3w1b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tfl3w1b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:business-idea-money-remix" {...props}></Icon>
