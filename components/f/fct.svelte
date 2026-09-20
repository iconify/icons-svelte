<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwf_gumjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwf_gumjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fct" {...props}></Icon>
