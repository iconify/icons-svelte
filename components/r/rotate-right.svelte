<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo7eluban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo7eluban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rotate-right" {...props}></Icon>
