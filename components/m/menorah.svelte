<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnkee_b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wnkee_b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:menorah" {...props}></Icon>
