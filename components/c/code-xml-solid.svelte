<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tob1ebbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tob1ebbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:code-xml-solid" {...props}></Icon>
