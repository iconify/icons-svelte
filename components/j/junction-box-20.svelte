<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9a328d8s.css';
import '../../css/t/thuizfb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9a328d8s"/><path class="thuizfb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:junction-box-20" {...props}></Icon>
