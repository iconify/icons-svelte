<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5tn1bc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f5tn1bc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hail-20" {...props}></Icon>
