<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymicfbb2j.css';
import '../../css/r/rhba1dbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymicfbb2j"/><path class="rhba1dbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:headset-outline" {...props}></Icon>
