<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flxvxybxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flxvxybxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fuel-round" {...props}></Icon>
