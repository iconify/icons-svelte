<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op3lkbbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op3lkbbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-1-0" {...props}></Icon>
