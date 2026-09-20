<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/newsskqet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="newsskqet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arch-linux-light" {...props}></Icon>
