<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch-5vob4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch-5vob4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-minus-fill-round" {...props}></Icon>
