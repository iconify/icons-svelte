<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmb9b00_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jmb9b00_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kjell-company-light" {...props}></Icon>
