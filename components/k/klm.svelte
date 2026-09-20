<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzt8752op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzt8752op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:klm" {...props}></Icon>
