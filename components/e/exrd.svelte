<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4m1lwmql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4m1lwmql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:exrd" {...props}></Icon>
