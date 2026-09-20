<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_4rf8b5k.css';
import '../../css/y/yctwq2t0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_4rf8b5k"/><path class="yctwq2t0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:espiral-book-light" {...props}></Icon>
