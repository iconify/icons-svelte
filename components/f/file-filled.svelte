<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_a7_nbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_a7_nbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-filled" {...props}></Icon>
