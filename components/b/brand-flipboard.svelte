<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq44l9b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq44l9b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-flipboard" {...props}></Icon>
