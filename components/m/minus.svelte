<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6t1upw1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6t1upw1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:minus" {...props}></Icon>
