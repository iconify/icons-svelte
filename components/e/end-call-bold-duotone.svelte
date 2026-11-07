<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfwi7necl.css';
import '../../css/b/bohfcinem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfwi7necl"/><path class="bohfcinem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-bold-duotone" {...props}></Icon>
