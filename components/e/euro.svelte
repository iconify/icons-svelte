<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4a7u515u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4a7u515u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:euro" {...props}></Icon>
