<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v532zufdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v532zufdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:grass-in-water" {...props}></Icon>
