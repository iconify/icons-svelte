<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j05r12o9z.css';
import '../../css/y/yslzmeb8y.css';
import '../../css/j/jwcfy35xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j05r12o9z"/><path class="yslzmeb8y"/><path clip-rule="evenodd" class="jwcfy35xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-bold-duotone" {...props}></Icon>
