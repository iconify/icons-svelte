<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7xzan34v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7xzan34v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:navigation-off-01" {...props}></Icon>
