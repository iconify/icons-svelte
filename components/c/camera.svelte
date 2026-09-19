<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zux88jbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zux88jbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:camera" {...props}></Icon>
