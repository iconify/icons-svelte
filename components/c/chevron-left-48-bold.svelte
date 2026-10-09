<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb91-bjyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pb91-bjyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-left-48-bold" {...props}></Icon>
