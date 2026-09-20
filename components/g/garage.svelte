<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6gff_n3z.css';
import '../../css/p/pnvwxie9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6gff_n3z"/><path class="pnvwxie9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garage" {...props}></Icon>
