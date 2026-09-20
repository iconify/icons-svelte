<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly4d_7b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly4d_7b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pin-1-remix" {...props}></Icon>
