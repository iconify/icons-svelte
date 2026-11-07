<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi6qtibex.css';
import '../../css/s/s02o69bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6qtibex"/><path class="s02o69bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-dropped-rounded-bold-duotone" {...props}></Icon>
