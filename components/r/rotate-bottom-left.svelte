<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn9r8cc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn9r8cc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-bottom-left" {...props}></Icon>
