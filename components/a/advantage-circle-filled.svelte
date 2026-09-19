<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubv59m5ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ubv59m5ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:advantage-circle-filled" {...props}></Icon>
