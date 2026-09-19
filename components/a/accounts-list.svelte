<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssr9qfzls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ssr9qfzls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:accounts-list" {...props}></Icon>
