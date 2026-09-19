<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i77zc0m-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i77zc0m-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:quote" {...props}></Icon>
