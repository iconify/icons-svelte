<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgj-uccys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgj-uccys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-wrapping-clip" {...props}></Icon>
