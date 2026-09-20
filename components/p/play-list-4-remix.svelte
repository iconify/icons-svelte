<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6nv8rb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y6nv8rb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:play-list-4-remix" {...props}></Icon>
