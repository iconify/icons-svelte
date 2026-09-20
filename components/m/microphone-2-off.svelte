<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evzh2560b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evzh2560b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:microphone-2-off" {...props}></Icon>
