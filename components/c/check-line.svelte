<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqb7atbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqb7atbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:check-line" {...props}></Icon>
