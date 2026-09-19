<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye8rm259n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ye8rm259n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rectangle-list" {...props}></Icon>
