<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5eou4ady.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s5eou4ady"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:btdx" {...props}></Icon>
