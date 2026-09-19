<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogxac5byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ogxac5byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fish" {...props}></Icon>
