<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i02gv5wud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i02gv5wud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-square-info" {...props}></Icon>
