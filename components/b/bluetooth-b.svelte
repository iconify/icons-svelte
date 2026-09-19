<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qto7n0ozo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1792};
const content = `<path class="qto7n0ozo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bluetooth-b" {...props}></Icon>
