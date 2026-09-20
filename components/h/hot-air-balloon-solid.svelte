<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znvl5qgur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="znvl5qgur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hot-air-balloon-solid" {...props}></Icon>
