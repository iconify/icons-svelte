<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyd8q7b-w.css';
import '../../css/x/x4db5135n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyd8q7b-w"/><path class="x4db5135n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-forward-duotone" {...props}></Icon>
