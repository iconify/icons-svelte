<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nap_aybed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nap_aybed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:database-fill-12" {...props}></Icon>
