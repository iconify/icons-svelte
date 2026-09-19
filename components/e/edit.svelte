<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u01qd4b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u01qd4b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:edit" {...props}></Icon>
