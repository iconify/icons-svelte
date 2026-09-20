<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfk3eub9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfk3eub9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-up-circle-line" {...props}></Icon>
