<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t43humgww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t43humgww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-bing-light" {...props}></Icon>
