<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maueyoblv.css';
import '../../css/y/ymcl-hbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="maueyoblv"/><path class="ymcl-hbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pills-add" {...props}></Icon>
