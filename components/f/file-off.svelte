<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwto3nb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwto3nb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-off" {...props}></Icon>
