<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8g12lbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u8g12lbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:gather-filled" {...props}></Icon>
