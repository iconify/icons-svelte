<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm2to1brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm2to1brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-arrow-up-right-filled" {...props}></Icon>
