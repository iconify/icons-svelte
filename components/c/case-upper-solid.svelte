<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfljatjfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfljatjfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:case-upper-solid" {...props}></Icon>
