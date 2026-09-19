<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzj9qebqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzj9qebqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:hammer-solid" {...props}></Icon>
