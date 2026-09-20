<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msawb0uon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="msawb0uon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bookmark-minus-f" {...props}></Icon>
