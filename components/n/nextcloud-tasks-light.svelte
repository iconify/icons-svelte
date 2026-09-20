<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu1n_0w8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu1n_0w8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-tasks-light" {...props}></Icon>
