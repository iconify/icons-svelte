<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm5jskbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zm5jskbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:passport-globe-remix" {...props}></Icon>
