<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyp7lccqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wyp7lccqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-haze" {...props}></Icon>
