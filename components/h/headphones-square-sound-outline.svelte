<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rajmnv0sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rajmnv0sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:headphones-square-sound-outline" {...props}></Icon>
