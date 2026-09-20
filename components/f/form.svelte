<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhw9w1klx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yhw9w1klx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:form" {...props}></Icon>
