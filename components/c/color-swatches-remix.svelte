<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqi0vz2bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sqi0vz2bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:color-swatches-remix" {...props}></Icon>
