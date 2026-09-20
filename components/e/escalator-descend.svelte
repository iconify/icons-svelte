<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a41c0cirg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a41c0cirg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:escalator-descend" {...props}></Icon>
