<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6oo7nb8e.css';
import '../../css/p/phxmbeb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a6oo7nb8e"/><path class="phxmbeb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pomerium-dark" {...props}></Icon>
