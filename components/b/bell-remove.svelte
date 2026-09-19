<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyj129fbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyj129fbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bell-remove" {...props}></Icon>
