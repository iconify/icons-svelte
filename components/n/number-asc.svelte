<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfasuabrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="vfasuabrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:number-asc" {...props}></Icon>
