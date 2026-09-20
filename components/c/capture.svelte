<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pms1zobcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pms1zobcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:capture" {...props}></Icon>
