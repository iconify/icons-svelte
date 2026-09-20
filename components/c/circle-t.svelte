<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-6_ylk_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-6_ylk_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-t" {...props}></Icon>
