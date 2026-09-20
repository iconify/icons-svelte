<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azdb_bbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azdb_bbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-key-filled" {...props}></Icon>
