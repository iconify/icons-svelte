<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjxrqjgru.css';
import '../../css/a/ads37eh-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjxrqjgru"/><path class="ads37eh-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:archive-alt" {...props}></Icon>
