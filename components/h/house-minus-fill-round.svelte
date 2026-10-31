<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qays_7b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qays_7b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-minus-fill-round" {...props}></Icon>
