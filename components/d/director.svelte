<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny7ki_z7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="ny7ki_z7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:director" {...props}></Icon>
