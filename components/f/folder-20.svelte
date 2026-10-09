<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk8kloxbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jk8kloxbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-20" {...props}></Icon>
