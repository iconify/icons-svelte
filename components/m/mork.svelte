<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6lpuzb1n.css';
import '../../css/p/pkogtxbhl.css';
import '../../css/o/o0054bc1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6lpuzb1n"/><path clip-rule="evenodd" class="pkogtxbhl"/><path class="o0054bc1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mork" {...props}></Icon>
