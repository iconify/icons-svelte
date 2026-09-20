<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x72ag7b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x72ag7b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:electric-cord-3-solid" {...props}></Icon>
