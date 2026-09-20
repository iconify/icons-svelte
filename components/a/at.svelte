<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw3ggguzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tw3ggguzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:at" {...props}></Icon>
