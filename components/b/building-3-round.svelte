<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qduqn3niy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qduqn3niy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-3-round" {...props}></Icon>
