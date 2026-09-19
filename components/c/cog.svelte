<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro67ohbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ro67ohbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:cog" {...props}></Icon>
