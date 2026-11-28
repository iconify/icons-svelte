<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e55-w7bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e55-w7bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:code-x" {...props}></Icon>
