<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ditspb6yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ditspb6yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ice-cream-1-solid" {...props}></Icon>
