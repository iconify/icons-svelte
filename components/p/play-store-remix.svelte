<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbese6xie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbese6xie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:play-store-remix" {...props}></Icon>
