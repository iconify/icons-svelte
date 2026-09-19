<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2jmd4b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2jmd4b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:building-alt-05-filled" {...props}></Icon>
