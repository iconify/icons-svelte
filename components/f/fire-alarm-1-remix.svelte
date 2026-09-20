<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i09db8b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i09db8b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fire-alarm-1-remix" {...props}></Icon>
