<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6s2--bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b6s2--bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:red-apple" {...props}></Icon>
