<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzntexeqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzntexeqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:expand" {...props}></Icon>
