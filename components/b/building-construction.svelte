<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx33p9m0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tx33p9m0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:building-construction" {...props}></Icon>
