<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdv0gpomk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdv0gpomk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-up-broken" {...props}></Icon>
