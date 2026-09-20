<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbk7imy3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbk7imy3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bell-set-timer-remix" {...props}></Icon>
