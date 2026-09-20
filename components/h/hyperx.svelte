<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1xtsm0jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1xtsm0jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hyperx" {...props}></Icon>
