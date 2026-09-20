<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ownt-qboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ownt-qboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mist" {...props}></Icon>
