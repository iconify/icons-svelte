<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/invhf0-gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="invhf0-gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-eur" {...props}></Icon>
