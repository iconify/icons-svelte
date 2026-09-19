<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aes_y_brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aes_y_brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:plastic" {...props}></Icon>
