<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1b5uxz9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1b5uxz9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:controls-forward-bold" {...props}></Icon>
