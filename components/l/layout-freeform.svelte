<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njo54y4mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njo54y4mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-freeform" {...props}></Icon>
