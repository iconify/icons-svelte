<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olf_s2qvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olf_s2qvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart5" {...props}></Icon>
