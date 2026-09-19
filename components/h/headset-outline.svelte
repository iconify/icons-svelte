<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/defuaabko.css';
import '../../css/n/n43_i1bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="defuaabko"/><path clip-rule="evenodd" class="n43_i1bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:headset-outline" {...props}></Icon>
