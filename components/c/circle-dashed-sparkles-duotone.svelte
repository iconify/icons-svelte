<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em39fubym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em39fubym primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dashed-sparkles-duotone" {...props}></Icon>
