<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpng5jbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpng5jbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:database-tag-solid" {...props}></Icon>
