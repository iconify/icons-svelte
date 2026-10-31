<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eedpgh6qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eedpgh6qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-minus-fill-round" {...props}></Icon>
