<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6tmqx8vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6tmqx8vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:package-arrow-right" {...props}></Icon>
