<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7qztxbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p7qztxbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:restart-square-filled" {...props}></Icon>
