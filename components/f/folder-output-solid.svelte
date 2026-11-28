<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg9xbxbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg9xbxbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-output-solid" {...props}></Icon>
