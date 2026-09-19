<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc2ta6dqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc2ta6dqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:remove-x-cross" {...props}></Icon>
