<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqho8nb-e.css';
import '../../css/k/k7wugp4nh.css';
import '../../css/h/hnviy2tvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqho8nb-e"/><path class="k7wugp4nh"/><path class="hnviy2tvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dalibo" {...props}></Icon>
