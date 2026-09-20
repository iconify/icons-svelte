<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiq-yuotc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="tiq-yuotc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:arrow-up" {...props}></Icon>
