<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cebdwg14u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cebdwg14u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:clean-broom-wipe-remix" {...props}></Icon>
