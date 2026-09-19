<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6gp9gbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6gp9gbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chocolate" {...props}></Icon>
