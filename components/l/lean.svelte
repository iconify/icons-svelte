<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqme3kbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":4.5,"height":4.5,"left":-2,"top":-2};
const content = `<path class="uqme3kbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lean" {...props}></Icon>
