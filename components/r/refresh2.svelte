<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aynmfmbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aynmfmbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh2" {...props}></Icon>
