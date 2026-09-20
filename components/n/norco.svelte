<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij8-4-wub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8-4-wub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:norco" {...props}></Icon>
