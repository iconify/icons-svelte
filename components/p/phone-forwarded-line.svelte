<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwef98_no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwef98_no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-forwarded-line" {...props}></Icon>
