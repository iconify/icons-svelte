<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7n3b9bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7n3b9bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:record-player-solid" {...props}></Icon>
