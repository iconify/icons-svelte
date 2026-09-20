<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tin4jwbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tin4jwbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piwigo-light" {...props}></Icon>
