<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6j7f0r3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6j7f0r3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bug-remix" {...props}></Icon>
