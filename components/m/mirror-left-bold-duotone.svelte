<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puwao6b5b.css';
import '../../css/j/jcvro1hvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puwao6b5b"/><path clip-rule="evenodd" class="jcvro1hvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-left-bold-duotone" {...props}></Icon>
