<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8fewte9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8fewte9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-chart-check" {...props}></Icon>
