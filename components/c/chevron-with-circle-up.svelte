<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb4dsrbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qb4dsrbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-with-circle-up" {...props}></Icon>
