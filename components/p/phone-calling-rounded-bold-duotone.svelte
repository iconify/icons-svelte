<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s02o69bfv.css';
import '../../css/y/yslzmeb8y.css';
import '../../css/j/jwcfy35xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s02o69bfv"/><path class="yslzmeb8y"/><path clip-rule="evenodd" class="jwcfy35xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-rounded-bold-duotone" {...props}></Icon>
