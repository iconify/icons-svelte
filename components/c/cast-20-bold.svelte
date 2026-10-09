<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7g4iqb1i.css';
import '../../css/m/mwlvaabdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b7g4iqb1i"/><path class="mwlvaabdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cast-20-bold" {...props}></Icon>
