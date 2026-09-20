<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi4wy58vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi4wy58vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:radius-bottom-right" {...props}></Icon>
