<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie7qaeb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie7qaeb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bank-fill" {...props}></Icon>
