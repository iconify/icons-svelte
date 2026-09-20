<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxb4qkbhf.css';
import '../../css/i/ivphhvj4r.css';
import '../../css/p/p4rsgjvps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oxb4qkbhf"/><path clip-rule="evenodd" class="ivphhvj4r"/><path class="p4rsgjvps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:jack-locked-16" {...props}></Icon>
