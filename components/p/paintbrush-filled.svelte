<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plbydi12c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plbydi12c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paintbrush-filled" {...props}></Icon>
