<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fohjow7uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fohjow7uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:acm" {...props}></Icon>
