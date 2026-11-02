<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8l04ubve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8l04ubve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:background-base-fill" {...props}></Icon>
