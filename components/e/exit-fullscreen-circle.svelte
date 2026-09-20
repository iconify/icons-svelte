<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe02l7sqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oe02l7sqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:exit-fullscreen-circle" {...props}></Icon>
