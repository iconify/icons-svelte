<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etl9yb0xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etl9yb0xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:freecodecamp" {...props}></Icon>
