<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sikot-83c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sikot-83c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:credit-card" {...props}></Icon>
