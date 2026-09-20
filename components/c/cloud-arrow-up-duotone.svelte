<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujwr_lkax.css';
import '../../css/d/dr-g6zfdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwr_lkax"/><path class="dr-g6zfdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-arrow-up-duotone" {...props}></Icon>
