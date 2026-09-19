<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3e92imgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s3e92imgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:falcon-moon" {...props}></Icon>
