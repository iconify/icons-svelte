<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6kss8baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6kss8baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:house-03" {...props}></Icon>
