<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayd1wfizv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayd1wfizv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lock-search" {...props}></Icon>
