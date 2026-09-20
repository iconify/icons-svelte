<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt76ptv6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt76ptv6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-big" {...props}></Icon>
