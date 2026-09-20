<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8pfxrb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8pfxrb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-dark" {...props}></Icon>
