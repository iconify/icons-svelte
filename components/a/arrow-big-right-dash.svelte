<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8pyyfbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8pyyfbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-right-dash" {...props}></Icon>
