<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-jwpob4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-jwpob4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:buss" {...props}></Icon>
