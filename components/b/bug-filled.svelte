<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_xeicb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_xeicb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bug-filled" {...props}></Icon>
