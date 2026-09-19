<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9h4j1-rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="a9h4j1-rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:fish" {...props}></Icon>
