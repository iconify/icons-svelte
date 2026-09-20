<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuwgi8b7w.css';
import '../../css/u/u8r_c8bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuwgi8b7w"/><path class="u8r_c8bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:link-h" {...props}></Icon>
