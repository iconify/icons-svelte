<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2zq4yb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2zq4yb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:root-me" {...props}></Icon>
