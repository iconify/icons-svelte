<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3bwd3b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3bwd3b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:package-filled" {...props}></Icon>
