<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iukgmv2cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iukgmv2cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:refresh" {...props}></Icon>
