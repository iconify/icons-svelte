<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y30wmue-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="y30wmue-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:next-light" {...props}></Icon>
