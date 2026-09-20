<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxkqfm6nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxkqfm6nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gift-fill" {...props}></Icon>
