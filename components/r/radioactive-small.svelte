<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-vex2b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f-vex2b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:radioactive-small" {...props}></Icon>
