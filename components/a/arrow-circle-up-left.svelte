<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltckgwbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltckgwbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-circle-up-left" {...props}></Icon>
