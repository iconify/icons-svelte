<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjqv5cbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjqv5cbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-florin" {...props}></Icon>
