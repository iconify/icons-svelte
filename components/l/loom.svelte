<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6oy2o_6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6oy2o_6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:loom" {...props}></Icon>
