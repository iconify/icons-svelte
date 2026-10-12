<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3hqbvbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3hqbvbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-circle-fill-20" {...props}></Icon>
