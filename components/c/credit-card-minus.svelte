<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0xf8_tbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0xf8_tbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:credit-card-minus" {...props}></Icon>
