<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty1qptbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":384};
const content = `<path class="ty1qptbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:audio" {...props}></Icon>
