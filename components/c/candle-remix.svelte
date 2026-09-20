<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrvvvy99u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mrvvvy99u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:candle-remix" {...props}></Icon>
