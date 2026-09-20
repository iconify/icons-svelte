<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4b3j5znj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4b3j5znj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bars-progress-fill" {...props}></Icon>
