<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4q057b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4q057b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:element-dark" {...props}></Icon>
