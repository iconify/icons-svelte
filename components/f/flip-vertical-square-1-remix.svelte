<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsrgl4t2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsrgl4t2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:flip-vertical-square-1-remix" {...props}></Icon>
