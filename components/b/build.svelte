<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-7fv8ivv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="l-7fv8ivv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:build" {...props}></Icon>
