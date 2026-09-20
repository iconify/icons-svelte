<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_n5z_b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_n5z_b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-move-up-1-remix" {...props}></Icon>
