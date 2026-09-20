<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5a7vubch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5a7vubch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-firefly-dark" {...props}></Icon>
