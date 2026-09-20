<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w72eddcir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w72eddcir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:messages-bubble-square-question-bold" {...props}></Icon>
