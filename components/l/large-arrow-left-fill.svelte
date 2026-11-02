<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or-a9mb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or-a9mb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-left-fill" {...props}></Icon>
