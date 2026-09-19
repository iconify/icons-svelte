<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auhox3b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auhox3b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:code" {...props}></Icon>
