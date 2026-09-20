<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_-kfbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae_-kfbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:private-internet-access-light" {...props}></Icon>
