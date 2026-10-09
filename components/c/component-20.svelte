<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeuw46sqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xeuw46sqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:component-20" {...props}></Icon>
