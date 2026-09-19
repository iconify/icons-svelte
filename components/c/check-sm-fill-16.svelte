<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-n4i5b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c-n4i5b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-sm-fill-16" {...props}></Icon>
