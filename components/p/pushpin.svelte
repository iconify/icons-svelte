<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8q964p-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o8q964p-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pushpin" {...props}></Icon>
