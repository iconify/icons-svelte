<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7nwo27os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7nwo27os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-narrow-left" {...props}></Icon>
