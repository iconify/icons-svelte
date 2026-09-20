<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzq3d_byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzq3d_byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:fiber-access-1-bold" {...props}></Icon>
