<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obkzbuqnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obkzbuqnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-list-x" {...props}></Icon>
