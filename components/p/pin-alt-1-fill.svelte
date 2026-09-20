<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr9bynb9b.css';
import '../../css/g/gxyna80vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hr9bynb9b"/><path class="gxyna80vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pin-alt-1-fill" {...props}></Icon>
