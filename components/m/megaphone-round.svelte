<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6qg4zccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6qg4zccu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:megaphone-round" {...props}></Icon>
