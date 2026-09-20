<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-37te37d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-37te37d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:call-minus-filled" {...props}></Icon>
