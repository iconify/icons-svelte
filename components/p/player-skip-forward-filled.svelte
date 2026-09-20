<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syjqo3h7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syjqo3h7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-skip-forward-filled" {...props}></Icon>
