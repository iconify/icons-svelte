<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_75qsb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_75qsb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-text-filled" {...props}></Icon>
