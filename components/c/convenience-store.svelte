<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbn6zo7il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="sbn6zo7il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:convenience-store" {...props}></Icon>
