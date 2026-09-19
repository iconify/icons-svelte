<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2pcyob-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="q2pcyob-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hourglass-start" {...props}></Icon>
