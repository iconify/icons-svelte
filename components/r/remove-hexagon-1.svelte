<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ekuzdlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7ekuzdlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:remove-hexagon-1" {...props}></Icon>
