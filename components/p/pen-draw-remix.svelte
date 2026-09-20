<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb8hm84kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tb8hm84kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pen-draw-remix" {...props}></Icon>
