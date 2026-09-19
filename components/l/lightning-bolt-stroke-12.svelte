<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulu84p6_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ulu84p6_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightning-bolt-stroke-12" {...props}></Icon>
