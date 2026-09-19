<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybntw-bao.css';
import '../../css/u/ut2il9b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybntw-bao"/><path class="ut2il9b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:eye-closed-solid" {...props}></Icon>
