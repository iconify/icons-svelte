<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it8p9ubjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="it8p9ubjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:playstation3" {...props}></Icon>
