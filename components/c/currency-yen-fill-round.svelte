<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc_mnpbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_mnpbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-yen-fill-round" {...props}></Icon>
