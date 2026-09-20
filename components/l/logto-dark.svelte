<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8nfsfvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ba8nfsfvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logto-dark" {...props}></Icon>
