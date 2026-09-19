<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3kc6x8kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g3kc6x8kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alt-text-fill-12" {...props}></Icon>
