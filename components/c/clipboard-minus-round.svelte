<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv237ms-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv237ms-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-minus-round" {...props}></Icon>
