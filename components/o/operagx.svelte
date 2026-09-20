<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrc4qfb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrc4qfb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:operagx" {...props}></Icon>
