<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyo2-_1op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tyo2-_1op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:brightness-1-remix" {...props}></Icon>
