<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4v05cb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4v05cb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hexagon-filled" {...props}></Icon>
