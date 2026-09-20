<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u77j4kbnz.css';
import '../../css/c/c-z8pxbpl.css';
import '../../css/h/hrh2fcbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u77j4kbnz"/><path clip-rule="evenodd" class="c-z8pxbpl"/><path class="hrh2fcbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:accumulator-bold-duotone" {...props}></Icon>
