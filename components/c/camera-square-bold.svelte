<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnf9n1bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nnf9n1bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-square-bold" {...props}></Icon>
