<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bikxxac2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bikxxac2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:close-round-light" {...props}></Icon>
