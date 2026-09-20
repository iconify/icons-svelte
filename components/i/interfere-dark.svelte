<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brj83-_4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":60};
const content = `<path class="brj83-_4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:interfere-dark" {...props}></Icon>
