<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc9yycyos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc9yycyos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:camera" {...props}></Icon>
