<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ywknb6x.css';
import '../../css/g/gf6bg710v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ywknb6x"/><path class="gf6bg710v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:heartbeat-solid" {...props}></Icon>
