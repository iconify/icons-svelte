<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhbjm3lzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhbjm3lzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-plus-solid" {...props}></Icon>
