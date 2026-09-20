<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdz_prbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mdz_prbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:optin-monster" {...props}></Icon>
