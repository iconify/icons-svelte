<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8ahujozp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8ahujozp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:file-arrow-up" {...props}></Icon>
