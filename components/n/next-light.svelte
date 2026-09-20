<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqlswxbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wqlswxbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:next-light" {...props}></Icon>
