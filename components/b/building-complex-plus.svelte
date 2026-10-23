<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns-0mfl4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns-0mfl4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:building-complex-plus" {...props}></Icon>
