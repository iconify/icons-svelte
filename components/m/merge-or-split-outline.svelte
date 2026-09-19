<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbcsn98cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbcsn98cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:merge-or-split-outline" {...props}></Icon>
