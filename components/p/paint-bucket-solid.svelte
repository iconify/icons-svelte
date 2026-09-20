<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itgze75et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="itgze75et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:paint-bucket-solid" {...props}></Icon>
