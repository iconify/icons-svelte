<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlwr8pbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zlwr8pbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rock-slide-remix" {...props}></Icon>
