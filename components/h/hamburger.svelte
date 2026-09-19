<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huuh1n9cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="huuh1n9cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hamburger" {...props}></Icon>
