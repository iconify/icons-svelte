<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_0iyzb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j_0iyzb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:address-book" {...props}></Icon>
