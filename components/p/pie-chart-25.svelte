<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-_tg5nyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-_tg5nyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:pie-chart-25" {...props}></Icon>
