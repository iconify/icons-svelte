<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpzn7xbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpzn7xbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dollar-increase-remix" {...props}></Icon>
