<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsuwm0btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsuwm0btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:package-minus" {...props}></Icon>
