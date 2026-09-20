<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obw2w46mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obw2w46mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:italic-sharp-duotone" {...props}></Icon>
