<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf1lk_bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf1lk_bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contact-lock" {...props}></Icon>
