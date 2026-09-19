<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnv37kbxp.css';
import '../../css/r/r-mn_3bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnv37kbxp"/><path class="r-mn_3bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:play-circle-alt-filled" {...props}></Icon>
