<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c94uocc5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c94uocc5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flower-solid" {...props}></Icon>
