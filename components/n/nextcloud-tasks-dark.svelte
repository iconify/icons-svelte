<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahxjtbgjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahxjtbgjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-tasks-dark" {...props}></Icon>
