<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zojmpb3mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zojmpb3mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bracket-arrow-up-fill" {...props}></Icon>
