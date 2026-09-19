<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq13s4qpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq13s4qpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:do-not-skateboard-rollerboard" {...props}></Icon>
