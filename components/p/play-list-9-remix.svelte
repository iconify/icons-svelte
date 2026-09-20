<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsktgzhvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zsktgzhvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:play-list-9-remix" {...props}></Icon>
