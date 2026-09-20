<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9_jpg2jv.css';
import '../../css/c/c287m3bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9_jpg2jv"/><path clip-rule="evenodd" class="c287m3bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-duotone" {...props}></Icon>
