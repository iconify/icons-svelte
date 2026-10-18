<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4z1uqb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4z1uqb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-left-dash" {...props}></Icon>
