<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8guv1byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8guv1byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clipboard-check-outline" {...props}></Icon>
