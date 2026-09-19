<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh5r6jayr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jh5r6jayr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bus-alt" {...props}></Icon>
