<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymk6fnbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ymk6fnbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:closet-remix" {...props}></Icon>
