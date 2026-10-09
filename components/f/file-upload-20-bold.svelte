<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8im5qk_h.css';
import '../../css/i/igzi4qboy.css';
import '../../css/v/vqn5vt5cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="igzi4qboy"/><path class="vqn5vt5cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-upload-20-bold" {...props}></Icon>
