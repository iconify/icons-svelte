<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqkr8dk-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqkr8dk-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-x-sharp" {...props}></Icon>
