<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjwz8ybnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjwz8ybnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-x" {...props}></Icon>
