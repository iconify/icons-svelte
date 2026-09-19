<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c69mprb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="c69mprb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:building" {...props}></Icon>
