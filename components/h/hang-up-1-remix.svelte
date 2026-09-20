<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9xjerbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a9xjerbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hang-up-1-remix" {...props}></Icon>
