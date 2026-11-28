<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a011rbbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a011rbbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gem" {...props}></Icon>
