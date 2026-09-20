<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhf0-4f-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhf0-4f-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:andela" {...props}></Icon>
