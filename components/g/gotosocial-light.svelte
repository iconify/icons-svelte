<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzy7uyvnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vzy7uyvnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gotosocial-light" {...props}></Icon>
