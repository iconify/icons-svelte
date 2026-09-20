<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j49qtw8ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j49qtw8ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:keeper" {...props}></Icon>
