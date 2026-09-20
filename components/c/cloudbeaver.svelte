<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xllod5uya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xllod5uya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudbeaver" {...props}></Icon>
