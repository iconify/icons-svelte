<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr5o16b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr5o16b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:basket-plus" {...props}></Icon>
