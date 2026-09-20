<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_yenib_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_yenib_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-lock-remix" {...props}></Icon>
