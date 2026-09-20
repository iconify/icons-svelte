<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4kld0byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4kld0byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:knives-set-bold" {...props}></Icon>
