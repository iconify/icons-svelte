<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt-hrr_ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt-hrr_ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:hot-beverage" {...props}></Icon>
