<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuhhxew8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nuhhxew8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:bring-to-front" {...props}></Icon>
