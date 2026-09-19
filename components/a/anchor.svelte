<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikywg0ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ikywg0ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:anchor" {...props}></Icon>
