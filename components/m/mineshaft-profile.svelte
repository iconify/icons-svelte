<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_raaxovl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z_raaxovl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:mineshaft-profile" {...props}></Icon>
