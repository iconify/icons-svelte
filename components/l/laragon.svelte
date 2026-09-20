<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxx-bo3lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxx-bo3lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:laragon" {...props}></Icon>
