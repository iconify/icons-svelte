<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zyk_juu.css';
import '../../css/r/rh_8cbdbx.css';
import '../../css/w/wcr2m1pdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e8zyk_juu"/><path class="rh_8cbdbx"/><path class="wcr2m1pdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammeter-20" {...props}></Icon>
