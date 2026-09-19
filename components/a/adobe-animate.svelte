<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h07slsb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h07slsb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-animate" {...props}></Icon>
