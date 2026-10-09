<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvltjac2r.css';
import '../../css/f/fbhmvz7nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bvltjac2r"/><path class="fbhmvz7nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-off-20" {...props}></Icon>
