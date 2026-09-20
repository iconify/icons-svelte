<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyo1fpb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zyo1fpb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flight-landing" {...props}></Icon>
