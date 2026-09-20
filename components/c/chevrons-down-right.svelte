<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igso8l8pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="igso8l8pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-down-right" {...props}></Icon>
