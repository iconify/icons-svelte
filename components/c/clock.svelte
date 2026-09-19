<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzcy8-vtw.css';
import '../../css/f/fv9ax2bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzcy8-vtw"/><path class="fv9ax2bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:clock" {...props}></Icon>
