<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u78usi47j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u78usi47j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:figma" {...props}></Icon>
