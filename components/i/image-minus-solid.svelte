<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od1c0fb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od1c0fb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-minus-solid" {...props}></Icon>
