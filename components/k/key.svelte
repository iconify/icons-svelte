<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuqv_880o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuqv_880o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:key" {...props}></Icon>
