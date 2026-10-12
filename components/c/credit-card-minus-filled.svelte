<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdsjmcckg.css';
import '../../css/w/wagseebvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jdsjmcckg"/><path class="wagseebvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:credit-card-minus-filled" {...props}></Icon>
