<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du2qh3bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="du2qh3bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:html-five-remix" {...props}></Icon>
