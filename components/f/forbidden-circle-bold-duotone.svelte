<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwnu8vvwz.css';
import '../../css/a/ah0oz-g8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwnu8vvwz"/><path class="ah0oz-g8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forbidden-circle-bold-duotone" {...props}></Icon>
