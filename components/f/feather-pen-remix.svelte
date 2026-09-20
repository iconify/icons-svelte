<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qznw1qbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qznw1qbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:feather-pen-remix" {...props}></Icon>
