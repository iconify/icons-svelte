<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj9306bap.css';
import '../../css/j/jh0o79cyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nj9306bap"/><path class="jh0o79cyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kayak-20-bold" {...props}></Icon>
