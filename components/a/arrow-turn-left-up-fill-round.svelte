<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk2rrg9ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk2rrg9ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-left-up-fill-round" {...props}></Icon>
