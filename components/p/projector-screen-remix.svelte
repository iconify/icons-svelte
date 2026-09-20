<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxzjl9bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxzjl9bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:projector-screen-remix" {...props}></Icon>
