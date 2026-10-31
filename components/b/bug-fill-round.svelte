<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnup9mg6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnup9mg6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bug-fill-round" {...props}></Icon>
