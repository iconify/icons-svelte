<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui6pqfb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ui6pqfb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pier-on-water" {...props}></Icon>
