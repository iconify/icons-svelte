<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni1j1zb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="ni1j1zb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:cancel" {...props}></Icon>
