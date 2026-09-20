<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlqn90vhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlqn90vhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:insert-row-remix" {...props}></Icon>
