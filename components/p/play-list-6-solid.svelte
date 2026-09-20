<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e31b-bcfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e31b-bcfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:play-list-6-solid" {...props}></Icon>
