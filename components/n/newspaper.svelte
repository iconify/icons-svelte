<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jebob6j0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jebob6j0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:newspaper" {...props}></Icon>
