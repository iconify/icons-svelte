<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsjun-7mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsjun-7mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mattermost" {...props}></Icon>
