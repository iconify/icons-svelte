<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlfm0esoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlfm0esoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:play" {...props}></Icon>
