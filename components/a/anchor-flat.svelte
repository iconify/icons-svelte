<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dct3tmbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dct3tmbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:anchor-flat" {...props}></Icon>
