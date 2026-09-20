<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc_63cp2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc_63cp2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-retry" {...props}></Icon>
