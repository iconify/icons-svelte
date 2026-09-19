<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz-t8pb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-t8pb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:letter-bold-outline" {...props}></Icon>
