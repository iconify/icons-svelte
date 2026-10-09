<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq63fdbpf.css';
import '../../css/f/fuoorab6u.css';
import '../../css/b/bmhruu9eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vq63fdbpf"/><path class="fuoorab6u"/><path class="bmhruu9eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:guitar-20-bold" {...props}></Icon>
