<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu24srbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu24srbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:currency-eur" {...props}></Icon>
