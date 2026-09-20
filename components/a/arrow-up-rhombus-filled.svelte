<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u305y6bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u305y6bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-rhombus-filled" {...props}></Icon>
