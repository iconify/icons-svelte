<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo7i7561t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo7i7561t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:nose-smell-remix" {...props}></Icon>
