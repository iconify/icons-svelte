<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juxp6ccai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juxp6ccai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-undo-up-right" {...props}></Icon>
