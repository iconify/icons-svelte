<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifep767hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifep767hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-plus-minus" {...props}></Icon>
