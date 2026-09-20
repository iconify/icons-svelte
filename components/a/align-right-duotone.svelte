<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7cmimq3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7cmimq3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-duotone" {...props}></Icon>
