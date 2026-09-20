<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cixim8hiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cixim8hiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bicycle-bike-solid" {...props}></Icon>
