<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwq1ytbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="gwq1ytbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:electrician" {...props}></Icon>
