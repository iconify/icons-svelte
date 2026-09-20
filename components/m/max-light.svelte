<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4k-61htt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4k-61htt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:max-light" {...props}></Icon>
