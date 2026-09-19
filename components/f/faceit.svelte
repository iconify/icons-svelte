<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xep8ytzzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xep8ytzzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:faceit" {...props}></Icon>
