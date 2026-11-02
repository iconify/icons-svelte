<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp2ariv_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp2ariv_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chevrons-up-down-fill" {...props}></Icon>
