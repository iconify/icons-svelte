<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpmhlzbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cpmhlzbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:computer-chip-1-remix" {...props}></Icon>
