<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p52u5b7hp.css';
import '../../css/f/f7q9a2bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p52u5b7hp"/><path class="f7q9a2bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:close-20" {...props}></Icon>
