<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqip0ibbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqip0ibbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnivore-light" {...props}></Icon>
