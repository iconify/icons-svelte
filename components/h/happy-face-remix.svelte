<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abvwb5blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="abvwb5blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:happy-face-remix" {...props}></Icon>
