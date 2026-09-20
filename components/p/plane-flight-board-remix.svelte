<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb-bf3b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb-bf3b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:plane-flight-board-remix" {...props}></Icon>
