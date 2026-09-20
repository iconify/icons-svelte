<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6f84htr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gs6f84htr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:rock-and-roll-hand-remix" {...props}></Icon>
