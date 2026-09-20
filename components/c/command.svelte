<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jawcotb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jawcotb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:command" {...props}></Icon>
