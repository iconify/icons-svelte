<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dope4ccwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dope4ccwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:nodejs" {...props}></Icon>
