<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/org_560qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="org_560qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-word-fill" {...props}></Icon>
